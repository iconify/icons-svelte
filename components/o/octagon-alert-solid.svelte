<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnppv9g-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnppv9g-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:octagon-alert-solid" {...props}></Icon>
