<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikjibbc6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikjibbc6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-smile-plus" {...props}></Icon>
