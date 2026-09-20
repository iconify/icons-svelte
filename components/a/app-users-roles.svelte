<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa312fb4p.css';
import '../../css/f/fl2n-_b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oa312fb4p"/><path class="fl2n-_b6d ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-users-roles" {...props}></Icon>
