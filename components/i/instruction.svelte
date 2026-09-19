<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/x/xkue7kb9l.css';
import '../../css/c/cofazqb2f.css';
import '../../css/d/db-9zy_vl.css';
import '../../css/e/e42-6mb8q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEgcuvcab"><g class="hv130ab-t"><rect class="xkue7kb9l"/><path class="cofazqb2f"/><path class="db-9zy_vl"/><path class="e42-6mb8q"/></g></mask></defs><path mask="url(#SVGEgcuvcab)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:instruction" {...props}></Icon>
