<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em-ossnxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="em-ossnxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:feather" {...props}></Icon>
