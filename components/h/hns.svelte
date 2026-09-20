<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho936o10f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ho936o10f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hns" {...props}></Icon>
