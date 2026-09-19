<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_qjv0bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_qjv0bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:clipboard-edit" {...props}></Icon>
