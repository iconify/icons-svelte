<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y55n2cbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="y55n2cbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:castle-f" {...props}></Icon>
