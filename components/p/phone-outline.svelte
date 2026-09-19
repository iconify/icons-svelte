<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krz_n7ouz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krz_n7ouz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:phone-outline" {...props}></Icon>
