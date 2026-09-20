<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm2eallgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pm2eallgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-hospital" {...props}></Icon>
