<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvvar4bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvvar4bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openid" {...props}></Icon>
