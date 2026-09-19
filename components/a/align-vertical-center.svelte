<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orcu2zbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orcu2zbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:align-vertical-center" {...props}></Icon>
