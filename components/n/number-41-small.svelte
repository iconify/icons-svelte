<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk6l96bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk6l96bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-41-small" {...props}></Icon>
