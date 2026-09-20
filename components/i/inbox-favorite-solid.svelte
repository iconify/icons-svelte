<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5skcqr-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p5skcqr-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:inbox-favorite-solid" {...props}></Icon>
