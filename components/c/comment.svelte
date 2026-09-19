<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljysoab7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljysoab7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:comment" {...props}></Icon>
