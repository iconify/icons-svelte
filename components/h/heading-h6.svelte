<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9dr0ncsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9dr0ncsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:heading-h6" {...props}></Icon>
