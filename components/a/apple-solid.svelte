<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqpkmbbws.css';
import '../../css/m/m_5z3sbiy.css';
import '../../css/g/g8175488f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qqpkmbbws"/><path class="m_5z3sbiy"/><path class="g8175488f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:apple-solid" {...props}></Icon>
