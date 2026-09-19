<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekh-ymbqu.css';
import '../../css/k/k27hiquiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ekh-ymbqu"/><path class="k27hiquiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:duplicate-sharp" {...props}></Icon>
