<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsxu0ib6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsxu0ib6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clock-circle" {...props}></Icon>
