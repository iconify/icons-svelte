<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6lkjeh9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p6lkjeh9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cloud-minus" {...props}></Icon>
