<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e590lpq6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e590lpq6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:medical-cross" {...props}></Icon>
