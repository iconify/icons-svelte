<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3vkaobrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f3vkaobrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ear-speciality-remix" {...props}></Icon>
