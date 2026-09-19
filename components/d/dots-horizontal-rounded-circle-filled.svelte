<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-4bhxunp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-4bhxunp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dots-horizontal-rounded-circle-filled" {...props}></Icon>
