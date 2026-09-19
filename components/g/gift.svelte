<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vukoj8c0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vukoj8c0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:gift" {...props}></Icon>
