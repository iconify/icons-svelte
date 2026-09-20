<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oduvyo18i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oduvyo18i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:jpeg-logo-block" {...props}></Icon>
