<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi7u_f7uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi7u_f7uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-vertical-waves" {...props}></Icon>
