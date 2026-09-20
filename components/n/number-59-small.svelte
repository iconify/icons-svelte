<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh7i4nfjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh7i4nfjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-59-small" {...props}></Icon>
