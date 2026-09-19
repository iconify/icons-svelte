<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km61y45mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km61y45mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lock-open-alt" {...props}></Icon>
