<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-jlh--l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb-jlh--l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:restaurant-03" {...props}></Icon>
