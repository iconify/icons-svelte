<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geq4cpb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="geq4cpb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bluetooth-signal" {...props}></Icon>
