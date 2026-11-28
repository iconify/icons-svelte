<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6oue9_va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6oue9_va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-alert" {...props}></Icon>
