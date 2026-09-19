<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aecai_kku.css';
import '../../css/g/g-d1ckdau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="aecai_kku"/><path class="g-d1ckdau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nhibernate" {...props}></Icon>
