<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc4xlwb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc4xlwb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:double-square-fill" {...props}></Icon>
