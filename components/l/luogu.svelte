<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eva_pbbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eva_pbbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:luogu" {...props}></Icon>
