<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/l/lgob9ib9a.css';
import '../../css/f/f8ajmabuk.css';
import '../../css/f/fnzhv2l2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsMi0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsMi0)"><path class="lgob9ib9a"/><path class="f8ajmabuk"/><path class="fnzhv2l2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:mi" {...props}></Icon>
