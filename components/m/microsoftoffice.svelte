<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hos4-7jae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hos4-7jae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microsoftoffice" {...props}></Icon>
