<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol0yy7b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ol0yy7b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:coins-filled" {...props}></Icon>
