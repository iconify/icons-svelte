<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o19u6j1mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o19u6j1mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:expand" {...props}></Icon>
