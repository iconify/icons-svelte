<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cprchxb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cprchxb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bag-suitcase-add-plus-solid" {...props}></Icon>
