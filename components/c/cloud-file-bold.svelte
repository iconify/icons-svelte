<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh4v0zw4o.css';
import '../../css/a/a82paub2z.css';
import '../../css/o/ok1wrcikb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh4v0zw4o"/><path class="a82paub2z"/><path class="ok1wrcikb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cloud-file-bold" {...props}></Icon>
