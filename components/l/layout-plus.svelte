<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3qyhzrhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3qyhzrhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:layout-plus" {...props}></Icon>
