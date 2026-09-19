<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fso_kcrdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fso_kcrdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:at-circle" {...props}></Icon>
