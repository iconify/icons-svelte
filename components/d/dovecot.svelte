<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlqlljahb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlqlljahb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dovecot" {...props}></Icon>
