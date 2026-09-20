<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahewiz-0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahewiz-0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:milanote" {...props}></Icon>
