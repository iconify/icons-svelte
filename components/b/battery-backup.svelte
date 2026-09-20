<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5o--1q2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5o--1q2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-backup" {...props}></Icon>
