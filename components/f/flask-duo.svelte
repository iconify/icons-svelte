<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsfq9iban.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g_-wzjb_l.css';
import '../../css/z/zxv-swbgq.css';
import '../../css/z/z8axxibzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsfq9iban secondary"/><g class="dt0cm9dhy primary"><path class="g_-wzjb_l"/><path class="zxv-swbgq"/><path class="z8axxibzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flask-duo" {...props}></Icon>
