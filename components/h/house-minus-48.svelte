<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcse7wsih.css';
import '../../css/k/kdbvn80vp.css';
import '../../css/k/kem81wb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kcse7wsih"/><path class="kdbvn80vp"/><path class="kem81wb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-minus-48" {...props}></Icon>
