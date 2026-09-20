<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmg9u37la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmg9u37la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:beijingsubway" {...props}></Icon>
