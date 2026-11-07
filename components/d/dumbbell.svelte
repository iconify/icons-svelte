<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqpbyeb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqpbyeb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dumbbell" {...props}></Icon>
