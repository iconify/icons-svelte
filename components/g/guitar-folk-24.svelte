<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp_7xjl5p.css';
import '../../css/s/s27o98huz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp_7xjl5p"/><path class="s27o98huz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:guitar-folk-24" {...props}></Icon>
