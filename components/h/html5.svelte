<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u779_db3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u779_db3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:html5" {...props}></Icon>
