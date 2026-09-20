<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvlq6xbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvlq6xbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:navigation-question" {...props}></Icon>
