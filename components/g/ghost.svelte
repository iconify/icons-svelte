<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq_ua2hba.css';
import '../../css/l/l7pgvx7mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kq_ua2hba"/><path class="l7pgvx7mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ghost" {...props}></Icon>
