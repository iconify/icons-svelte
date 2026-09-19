<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqmgg0cqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqmgg0cqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:language" {...props}></Icon>
