<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/tj6aivbzl.css';
import '../../css/u/uyqxwgbgq.css';
import '../../css/w/wq8panzid.css';
import '../../css/o/o1xiohgss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><ellipse class="tj6aivbzl"/><path class="uyqxwgbgq"/><path class="wq8panzid"/><path class="o1xiohgss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:database-backup" {...props}></Icon>
