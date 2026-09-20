<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j814zviep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j814zviep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pycharm" {...props}></Icon>
