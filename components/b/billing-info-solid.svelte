<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcsyndb6q.css';
import '../../css/k/kzh5-ccpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcsyndb6q"/><path class="kzh5-ccpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:billing-info-solid" {...props}></Icon>
