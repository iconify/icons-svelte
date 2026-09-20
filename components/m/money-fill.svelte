<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owb0njbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="owb0njbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:money-fill" {...props}></Icon>
