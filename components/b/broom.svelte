<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq7wbxbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq7wbxbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:broom" {...props}></Icon>
