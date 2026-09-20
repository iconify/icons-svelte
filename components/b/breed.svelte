<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq_dl8bqj.css';
import '../../css/a/asuar4emf.css';
import '../../css/f/f8sf7yhpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq_dl8bqj"/><path class="asuar4emf"/><path class="f8sf7yhpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:breed" {...props}></Icon>
