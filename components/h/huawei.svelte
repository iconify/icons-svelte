<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l84cqnb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l84cqnb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:huawei" {...props}></Icon>
