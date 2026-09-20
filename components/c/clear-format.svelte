<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soaeigb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6.5,"top":-6.5};
const content = `<path class="soaeigb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:clear-format" {...props}></Icon>
