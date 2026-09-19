<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_n7dobql.css';
import '../../css/m/m6gu448fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_n7dobql"/><path class="m6gu448fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rotate-cw-30-filled" {...props}></Icon>
