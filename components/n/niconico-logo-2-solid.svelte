<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2g16ob1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o2g16ob1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:niconico-logo-2-solid" {...props}></Icon>
