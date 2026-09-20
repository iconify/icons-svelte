<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3lf2bcxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3lf2bcxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ath" {...props}></Icon>
