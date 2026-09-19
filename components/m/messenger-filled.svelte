<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pybkn4b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pybkn4b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:messenger-filled" {...props}></Icon>
