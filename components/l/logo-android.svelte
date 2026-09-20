<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bjjo0nbkw.css';
import '../../css/z/z0uh4cbbm.css';
import '../../css/y/ywpt9tc6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bjjo0nbkw"/><path class="z0uh4cbbm"/><path class="ywpt9tc6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-android" {...props}></Icon>
