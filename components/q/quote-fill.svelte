<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb_9edcci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb_9edcci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:quote-fill" {...props}></Icon>
