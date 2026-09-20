<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0cqmg3wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0cqmg3wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:filter-fill" {...props}></Icon>
