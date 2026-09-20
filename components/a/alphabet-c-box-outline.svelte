<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqr00dbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqr00dbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-c-box-outline" {...props}></Icon>
