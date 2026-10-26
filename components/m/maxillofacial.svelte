<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp6apm1sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mp6apm1sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:maxillofacial" {...props}></Icon>
