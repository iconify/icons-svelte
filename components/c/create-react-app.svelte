<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skz7itc8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skz7itc8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:create-react-app" {...props}></Icon>
