<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkj6lmbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkj6lmbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layout-panel-left-filled" {...props}></Icon>
