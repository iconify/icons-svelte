<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui4p003tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ui4p003tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:close-rectangle-f" {...props}></Icon>
