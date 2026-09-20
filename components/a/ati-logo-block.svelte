<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjrm1iu6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gjrm1iu6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:ati-logo-block" {...props}></Icon>
