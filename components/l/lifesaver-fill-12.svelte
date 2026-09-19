<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u33umgorm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="u33umgorm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lifesaver-fill-12" {...props}></Icon>
