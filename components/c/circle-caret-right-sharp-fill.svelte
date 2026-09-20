<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caa9iac3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="caa9iac3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-caret-right-sharp-fill" {...props}></Icon>
