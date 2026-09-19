<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlis81b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlis81b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:application" {...props}></Icon>
