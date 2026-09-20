<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-_f9rb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-_f9rb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart-diamond-solid" {...props}></Icon>
