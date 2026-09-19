<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se8m_e3yt.css';
import '../../css/h/hp28okb8j.css';
import '../../css/z/z040k9bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se8m_e3yt"/><path class="hp28okb8j"/><circle class="z040k9bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:read" {...props}></Icon>
