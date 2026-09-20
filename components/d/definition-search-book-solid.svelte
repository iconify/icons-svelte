<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phft6lxqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="phft6lxqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:definition-search-book-solid" {...props}></Icon>
