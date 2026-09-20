<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op92b2h4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op92b2h4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:laptop" {...props}></Icon>
