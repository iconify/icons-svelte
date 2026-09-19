<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee0hxn02z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":5,"height":24};
const content = `<path class="ee0hxn02z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:more-v-a" {...props}></Icon>
