<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltm588bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltm588bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:joomla" {...props}></Icon>
