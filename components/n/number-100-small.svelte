<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4gbwvw2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4gbwvw2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-100-small" {...props}></Icon>
