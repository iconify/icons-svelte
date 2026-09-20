<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tswetb8fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tswetb8fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:clock-ten" {...props}></Icon>
