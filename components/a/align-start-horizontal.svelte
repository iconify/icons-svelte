<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb77abcux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb77abcux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-start-horizontal" {...props}></Icon>
