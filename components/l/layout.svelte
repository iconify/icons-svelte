<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijmq62bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="ijmq62bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:layout" {...props}></Icon>
