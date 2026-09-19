<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpn7v4c7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpn7v4c7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:dots-horizontal" {...props}></Icon>
