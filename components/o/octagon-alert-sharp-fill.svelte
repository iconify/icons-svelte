<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g40yip9tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g40yip9tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:octagon-alert-sharp-fill" {...props}></Icon>
