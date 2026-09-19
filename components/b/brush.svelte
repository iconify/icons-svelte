<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9y9fhy5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9y9fhy5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:brush" {...props}></Icon>
