<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lce41nbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lce41nbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dumbbell" {...props}></Icon>
