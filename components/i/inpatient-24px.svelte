<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbt1owbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbt1owbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:inpatient-24px" {...props}></Icon>
