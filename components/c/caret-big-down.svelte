<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et7pcw8op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="et7pcw8op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-big-down" {...props}></Icon>
