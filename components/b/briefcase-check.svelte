<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxcp0ac0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxcp0ac0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:briefcase-check" {...props}></Icon>
