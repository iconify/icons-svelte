<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv7ye3m0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vv7ye3m0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-package-filled" {...props}></Icon>
