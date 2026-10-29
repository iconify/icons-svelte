<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh4rqfpek.css';
import '../../css/w/wx4dzibso.css';
import '../../css/k/kz669vh8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4rqfpek"/><path class="wx4dzibso"/><path class="kz669vh8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:align-justify" {...props}></Icon>
