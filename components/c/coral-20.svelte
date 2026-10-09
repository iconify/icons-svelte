<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfi4ayb5u.css';
import '../../css/l/ljp18512i.css';
import '../../css/e/eqwghdb8t.css';
import '../../css/p/pdcho1m7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kfi4ayb5u"/><path class="ljp18512i"/><path class="eqwghdb8t"/><path class="pdcho1m7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coral-20" {...props}></Icon>
