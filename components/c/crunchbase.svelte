<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l57u97ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l57u97ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:crunchbase" {...props}></Icon>
