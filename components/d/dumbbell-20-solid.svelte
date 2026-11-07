<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1it2bcqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="f1it2bcqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dumbbell-20-solid" {...props}></Icon>
