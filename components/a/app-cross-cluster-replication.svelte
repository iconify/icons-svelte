<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb78y2rwy.css';
import '../../css/t/tm8w-yurb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hb78y2rwy"/><path class="ouiIcon__fillSecondary tm8w-yurb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-cross-cluster-replication" {...props}></Icon>
