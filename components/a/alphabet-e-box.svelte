<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o39h_qb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o39h_qb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-e-box" {...props}></Icon>
