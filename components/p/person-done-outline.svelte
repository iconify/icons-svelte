<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm4tdhhde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm4tdhhde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:person-done-outline" {...props}></Icon>
